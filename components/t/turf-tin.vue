<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vunxkfbbd.css';
import '../../css/f/fsxxlibal.css';
import '../../css/o/okepkxbbb.css';
import '../../css/l/l3jht2pou.css';
import '../../css/x/xeze5zbrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<circle class="vunxkfbbd"/><circle class="fsxxlibal"/><circle class="okepkxbbb"/><circle class="l3jht2pou"/><path class="xeze5zbrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="geo:turf-tin" /></template>
