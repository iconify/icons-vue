<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq2q0_lyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="gq2q0_lyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:navigation-arrow-on-remix" /></template>
