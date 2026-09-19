<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1yk60bwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c1yk60bwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:video-alt2" /></template>
