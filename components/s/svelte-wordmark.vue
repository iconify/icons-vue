<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3bgbdlao.css';
import '../../css/l/ldp-e91yu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="a3bgbdlao"/><path class="ldp-e91yu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:svelte-wordmark" /></template>
