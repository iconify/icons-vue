<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqyxq6bhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mic-alert-rounded" /></template>
<style>
.kqyxq6bhi {
  fill: currentColor;
  d: path("M8.577 12.423Q8 11.846 8 11V5q0-.846.577-1.423T10 3t1.423.577T12 5v6q0 .846-.577 1.423T10 13t-1.423-.577m7.654 7.154q.2 0 .33-.13t.131-.331t-.13-.331t-.331-.131t-.331.13q-.13.132-.13.332t.13.33t.33.131m.274-2.035q.111-.111.111-.273v-2.461q0-.162-.111-.274q-.112-.111-.273-.111t-.273.111t-.112.274v2.461q0 .162.112.273t.273.112t.273-.112m-3.109 2.293Q12.231 18.672 12.231 17t1.164-2.835T16.231 13t2.835 1.165T20.231 17t-1.165 2.836T16.231 21t-2.836-1.164M9.5 20v-3.017q-2.165-.19-3.716-1.72q-1.551-1.529-1.748-3.738q-.03-.214.11-.37Q4.286 11 4.5 11t.357.153t.185.366q.202 1.875 1.592 3.156q1.389 1.28 3.283 1.28q.248 0 .416.191q.167.19.167.413V20q0 .214-.143.357T10 20.5t-.357-.143T9.5 20");
}

</style>
