<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-dh7vbso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e-dh7vbso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:tragedy-mask" /></template>
