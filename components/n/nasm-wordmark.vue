<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2twmofqo.css';
import '../../css/x/xsfvsus8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="x2twmofqo"/><path class="xsfvsus8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:nasm-wordmark" /></template>
