<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3ba3acpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":710};
const content = `<path class="g3ba3acpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:simplepie" /></template>
