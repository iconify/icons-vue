<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zh04-4b3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tab-new-right-rounded" /></template>
<style>
.zh04-4b3y {
  fill: currentColor;
  d: path("M20.367 19.5H16q-.213 0-.357-.143T15.5 19t.143-.357T16 18.5h4.367l-1.727-1.766q-.14-.14-.13-.34q.01-.202.155-.348q.14-.14.344-.14t.345.14l2.369 2.389q.243.242.243.565t-.243.566l-2.388 2.388q-.14.14-.342.133t-.347-.153q-.14-.14-.14-.334t.14-.334zm-8.867-7V16q0 .214.143.357T12 16.5t.357-.143T12.5 16v-3.5H16q.214 0 .357-.143T16.5 12t-.143-.357T16 11.5h-3.5V8q0-.213-.143-.357T12 7.5t-.357.143T11.5 8v3.5H8q-.213 0-.357.143T7.5 12t.143.357T8 12.5zM5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v6.996q0 .315-.244.535q-.245.22-.56.178q-1.213-.046-2.298.389q-1.084.434-1.917 1.267q-.827.827-1.267 1.908q-.441 1.08-.395 2.307q.012.315-.193.56t-.514.244z");
}

</style>
