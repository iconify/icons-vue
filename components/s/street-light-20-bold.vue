<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkophlb7r.css';
import '../../css/x/xiggllbmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xkophlb7r"/><path class="xiggllbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:street-light-20-bold" /></template>
