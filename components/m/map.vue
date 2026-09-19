<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cag2ndsks.css';
import '../../css/p/pdncx1b3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cag2ndsks"/><path class="pdncx1b3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:map" /></template>
