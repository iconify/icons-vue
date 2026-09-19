<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxvol2n9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zxvol2n9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:music-rhythm" /></template>
