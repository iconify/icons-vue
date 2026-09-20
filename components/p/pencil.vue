<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1nfpfxmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="a1nfpfxmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:pencil" /></template>
