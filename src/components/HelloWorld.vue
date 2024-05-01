<template>
  <div class="hello">
    <p>A film produced by Pana Film</p>
    <h3>Complete information about the movie</h3>
    <ul>
      <li><a href="https://www.panafilm.com/en/">About film</a></li>
    </ul>
    <h3>Link to watch movies</h3>
    <ul>
      <li><a href="https://www.dailymotion.com/video/x8itue5">Kurtlar Vadisi</a></li>
      <li><a href="https://jetfilmizle.de/kurtlar-vadisi-gladio-2009-izle-720p.html">Kurtlar Vadisi Gladio</a></li>
      <li><a href="https://www.diziizle.life/kurtlar-vadisi-pusu/bolum-1/">Kurtlar Vadisi Pusu</a></li>
      <li><a href="https://ok.ru/video/6503656000064">Kurtlar vadisi Irak</a></li>
      <li><a href="https://jetfilmizle.de/kurtlar-vadisi-filistin-full-izle.html">Kurtlar vadisi Filistin</a></li>
      <li><a href="https://vk.com/video-22595079_456239163">Kurtlar vadisi Vatan</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
  }
}
</script>

<style >
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #090085;
}
</style>
