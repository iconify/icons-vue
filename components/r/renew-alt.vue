<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn06qxi9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yn06qxi9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:renew-alt" /></template>
