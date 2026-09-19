<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2vq0hbyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u2vq0hbyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:pony" /></template>
