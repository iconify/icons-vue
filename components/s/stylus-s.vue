<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0oe59bah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":376,"height":512};
const content = `<path class="d0oe59bah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:stylus-s" /></template>
