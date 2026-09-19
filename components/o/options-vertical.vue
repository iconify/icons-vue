<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9hz590ry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9hz590ry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:options-vertical" /></template>
