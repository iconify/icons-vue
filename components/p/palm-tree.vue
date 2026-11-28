<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4kwgog3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4kwgog3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:palm-tree" /></template>
