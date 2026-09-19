<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf3eq6alg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="sf3eq6alg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:toggle-border" /></template>
