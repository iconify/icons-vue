<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b84sy2bnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b84sy2bnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:pencil-ruler" /></template>
