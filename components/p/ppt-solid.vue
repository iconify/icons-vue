<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spcbx1-oy.css';
import '../../css/b/beu2x0b4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="spcbx1-oy"/><path clip-rule="evenodd" class="beu2x0b4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:ppt-solid" /></template>
