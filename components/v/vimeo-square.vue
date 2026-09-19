<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlgp0hbjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="jlgp0hbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:vimeo-square" /></template>
