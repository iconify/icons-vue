<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lze9kx9yx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lze9kx9yx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rallly-dark" /></template>
