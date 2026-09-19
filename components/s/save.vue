<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuosmopkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="fuosmopkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:save" /></template>
