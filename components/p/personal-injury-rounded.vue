<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0yy_7kmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:personal-injury-rounded" /></template>
<style>
.x0yy_7kmm {
  fill: currentColor;
  d: path("M9.877 8.777Q9 7.9 9 6.654t.877-2.123T12 3.654t2.123.877T15 6.654t-.877 2.123T12 9.654t-2.123-.877m.373 10.185q-.44 0-.749-.309t-.309-.75t.309-.748t.749-.309h1.927q.217 0 .348.19q.13.189.025.4l-.542 1.085q-.106.218-.305.329q-.2.112-.422.112zm-3.92-6.104q1.328-.635 2.758-.997T12 11.5q.671 0 1.342.079t1.342.255q.218.05.314.24t-.01.401l-1.451 2.93q-.106.218-.305.33q-.2.111-.422.111h-2.56q-.861 0-1.46.598q-.598.598-.598 1.46q0 .477.18.866q.178.39.5.694q.16.13.12.314t-.22.184H5.807q-.348 0-.578-.23T5 19.154V14.86q0-.639.365-1.169q.364-.53.966-.833M19 18.346q0 .671-.472 1.144t-1.144.472h-.338q-.348 0-.578-.23t-.23-.578v-6.262q0-.217.174-.35q.174-.134.392-.048q.219.075.432.172q.214.098.433.192q.596.304.964.833q.367.53.367 1.168z");
}

</style>
