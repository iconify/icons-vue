<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6ctmtb6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w6ctmtb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:serverless" /></template>
