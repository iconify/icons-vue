<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5s15bc3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="p5s15bc3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:wifi-slash-20-solid" /></template>
