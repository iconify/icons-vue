<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsbym-9ml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsbym-9ml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:temperature-quarter-fill" /></template>
