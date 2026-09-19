<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4lyu_g1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="e4lyu_g1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:old-republic" /></template>
