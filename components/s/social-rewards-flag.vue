<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds994zbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ds994zbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:social-rewards-flag" /></template>
