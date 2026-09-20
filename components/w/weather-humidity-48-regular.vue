<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oa508acih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:weather-humidity-48-regular" /></template>
<style>
.oa508acih {
  fill: currentColor;
  d: path("M29.25 41.5a1.25 1.25 0 1 1 0 2.5h-10.5a1.25 1.25 0 1 1 0-2.5zm5.5-5a1.25 1.25 0 1 1 0 2.5h-21.5a1.25 1.25 0 1 1 0-2.5zm2-5a1.25 1.25 0 1 1 0 2.5h-25.5a1.25 1.25 0 1 1 0-2.5zm.5-5a1.25 1.25 0 1 1 0 2.5h-26.5a1.25 1.25 0 1 1 0-2.5zM24.001 4c.331 0 .65.132.884.366c.867.867 4.248 4.12 7.408 8.461c2.42 3.326 4.812 7.423 5.77 11.673H35.49c-.917-3.544-2.961-7.101-5.219-10.202c-2.37-3.255-4.871-5.875-6.27-7.283c-1.448 1.454-3.984 4.097-6.363 7.376c-2.23 3.072-4.235 6.585-5.135 10.109h-2.57c.941-4.226 3.284-8.276 5.681-11.578c3.13-4.31 6.513-7.565 7.503-8.556A1.25 1.25 0 0 1 24.001 4");
}

</style>
