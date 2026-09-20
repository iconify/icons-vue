<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clp7z2bgf.css';
import '../../css/u/u7sq-5xjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clp7z2bgf"/><path class="u7sq-5xjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:thunderstorm-fill" /></template>
