<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt2675bvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nt2675bvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:microphone-outline" /></template>
