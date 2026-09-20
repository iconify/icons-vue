<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5gxmyslj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tab-new-right-outline-rounded" /></template>
<style>
.j5gxmyslj {
  fill: currentColor;
  d: path("M5 19V5zm.616 1q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v7.076q0 .214-.143.357t-.357.143t-.357-.143t-.143-.357V5.616q0-.231-.192-.424T18.384 5H5.616q-.231 0-.424.192T5 5.616v12.769q0 .23.192.423t.423.192h7.077q.214 0 .357.143t.143.357t-.143.357t-.357.143zm14.751-.5H16q-.213 0-.357-.143T15.5 19t.143-.357T16 18.5h4.367l-1.727-1.766q-.14-.14-.13-.34q.01-.202.155-.348q.14-.14.344-.14t.345.14l2.369 2.389q.243.242.243.565t-.243.566l-2.388 2.388q-.14.14-.342.133t-.347-.153q-.14-.14-.14-.334t.14-.334zm-8.867-7V16q0 .214.143.357T12 16.5t.357-.143T12.5 16v-3.5H16q.214 0 .357-.143T16.5 12t-.143-.357T16 11.5h-3.5V8q0-.213-.143-.357T12 7.5t-.357.143T11.5 8v3.5H8q-.213 0-.357.143T7.5 12t.143.357T8 12.5z");
}

</style>
