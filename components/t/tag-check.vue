<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvj1bfbkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvj1bfbkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:tag-check" /></template>
