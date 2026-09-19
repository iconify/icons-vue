<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z91ewcb2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="z91ewcb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:windmill" /></template>
