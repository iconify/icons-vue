<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0ory7bry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":680,"height":661};
const content = `<path class="l0ory7bry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:sitemap" /></template>
