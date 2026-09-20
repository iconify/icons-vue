<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_ihi-nli.css';
import '../../css/r/rb93hspbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_ihi-nli"/><path class="rb93hspbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:map-search-1-filled" /></template>
