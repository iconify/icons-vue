<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4gl7ubxp.css';
import '../../css/m/m76ihyh3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q4gl7ubxp"/><path class="m76ihyh3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:repo-delete-16" /></template>
