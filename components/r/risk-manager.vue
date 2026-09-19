<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grigrjbrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grigrjbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:risk-manager" /></template>
