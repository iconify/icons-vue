<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ay2pi0bpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ay2pi0bpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:xrp-fill" /></template>
