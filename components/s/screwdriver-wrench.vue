<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp7hmqnvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="bp7hmqnvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:screwdriver-wrench" /></template>
