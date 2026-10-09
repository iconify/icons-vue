<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcw6mnbls.css';
import '../../css/m/m8t0x9bfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bcw6mnbls"/><path class="m8t0x9bfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pram-20" /></template>
