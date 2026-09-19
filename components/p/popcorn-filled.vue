<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epsxxyetc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epsxxyetc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:popcorn-filled" /></template>
