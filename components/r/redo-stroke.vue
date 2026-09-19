<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cj9e8cckx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cj9e8cckx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:redo-stroke" /></template>
