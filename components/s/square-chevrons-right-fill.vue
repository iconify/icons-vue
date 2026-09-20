<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfyy2kbzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfyy2kbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-chevrons-right-fill" /></template>
