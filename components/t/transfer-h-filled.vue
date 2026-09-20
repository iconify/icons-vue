<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cis5txmal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cis5txmal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:transfer-h-filled" /></template>
