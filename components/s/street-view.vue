<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5778rb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1408,"height":1760};
const content = `<path class="l5778rb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:street-view" /></template>
