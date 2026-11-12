<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr6cklb9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pr6cklb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pointer-spark" /></template>
