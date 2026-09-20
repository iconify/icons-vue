<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgyv4ac-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgyv4ac-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-arrow-up-linear" /></template>
