<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzv1y2bfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="pzv1y2bfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:top-left-solid" /></template>
