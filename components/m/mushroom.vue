<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ed9gmnbgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1023};
const content = `<path class="ed9gmnbgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:mushroom" /></template>
