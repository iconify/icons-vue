<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="sfsu6bjpq"/><circle class="vnwlyobeu"/><circle class="i-geqybed"/><circle class="d2oducc6e"/><circle class="thzoy2b-k"/><circle class="ah1ogjgvz"/><path class="o0jgzcbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tp-link-iot" /></template>
<style>
.ah1ogjgvz {
  cx: 10.565px;
  cy: 10.565px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.d2oducc6e {
  cx: 37.435px;
  cy: 10.565px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.i-geqybed {
  cx: 10.565px;
  cy: 37.435px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.o0jgzcbrh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.718 33.567l-.833 6.332m3.397-25.479l.833-6.332m-.833 25.479l.832 6.324m-3.396-25.47l-.833-6.333m2.609 11.954v7.903h3.951m2.404-7.903v7.903m-20.35 0v-7.903h2.587c1.463 0 2.649 1.188 2.649 2.654s-1.186 2.654-2.649 2.654H10.5m-7.64-5.308h5.236m-2.618 7.903v-7.903m27.775 7.903v-7.903l5.236 7.903v-7.903m-20.35 3.952h3.951m18.802-3.939v7.903m0-2.752l4.248-5.124m0 7.876l-3.25-3.952M24 8.75v4.75m0 21v4.737m10.779-26.022l-3.359 3.359M16.571 31.423l-3.35 3.35m0-21.558l3.359 3.359m14.849 14.849l3.35 3.35m-18.455-4.917l-5.067 3.888m20.42-15.613l5.066-3.888M18.137 31.669l-3.883 5.06m15.609-20.411l3.888-5.067m-2.075 18.605l5.067 3.888m-20.42-15.613l-5.066-3.888m18.606 17.426l3.883 5.06m-15.609-20.41L14.25 11.25");
}

.sfsu6bjpq {
  cx: 24px;
  cy: 5px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.thzoy2b-k {
  cx: 37.435px;
  cy: 37.435px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vnwlyobeu {
  cx: 24px;
  cy: 42.987px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
