<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onf7ubw3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="onf7ubw3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:settings" /></template>
