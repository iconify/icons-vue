<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjxa9--aw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjxa9--aw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:tree-pine-gloss" /></template>
