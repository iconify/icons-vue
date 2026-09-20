<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucovey0py"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:rectangle-add-outline-rounded" /></template>
<style>
.ucovey0py {
  fill: currentColor;
  d: path("M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19zm0-1h14.769q.23 0 .423-.192t.192-.424V6.616q0-.231-.192-.424T19.385 6H4.615q-.23 0-.423.192T4 6.616v10.769q0 .23.192.423t.423.192M4 18V6zm7.5-5.5V15q0 .214.143.357T12 15.5t.357-.143T12.5 15v-2.5H15q.214 0 .357-.143T15.5 12t-.143-.357T15 11.5h-2.5V9q0-.213-.143-.357T12 8.5t-.357.143T11.5 9v2.5H9q-.213 0-.357.143T8.5 12t.143.357T9 12.5z");
}

</style>
