<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8ka9_gel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g8ka9_gel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wc-text" /></template>
