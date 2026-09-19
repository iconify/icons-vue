<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywgjsyp3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":78,"height":26};
const content = `<path class="ywgjsyp3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:wordmark-explore-26" /></template>
