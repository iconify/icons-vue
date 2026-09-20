<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fr1x3v3sb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nfc" /></template>
<style>
.fr1x3v3sb {
  fill: currentColor;
  d: path("M8 16h8V8h-3.5q-.421 0-.71.29q-.29.289-.29.71v2.07q-.23.12-.404.344q-.173.223-.173.586q0 .46.299.768q.3.309.778.309q.421 0 .749-.309t.328-.768q0-.363-.179-.586q-.179-.224-.398-.345V9H15v6H9V9h1V8H8zm-2.384 4q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20z");
}

</style>
