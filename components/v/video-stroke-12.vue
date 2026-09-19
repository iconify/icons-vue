<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r06hjub7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="r06hjub7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:video-stroke-12" /></template>
