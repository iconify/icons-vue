<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jp27lvbgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jp27lvbgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:mercurial" /></template>
