<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tu5x9bbvk.css';
import '../../css/n/ndj5swlkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tu5x9bbvk"/><path class="ndj5swlkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:phone-search-filled" /></template>
