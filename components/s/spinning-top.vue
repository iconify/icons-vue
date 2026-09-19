<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu6ajdafw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iu6ajdafw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:spinning-top" /></template>
