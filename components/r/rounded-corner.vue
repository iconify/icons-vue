<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sw5z9db9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sw5z9db9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:rounded-corner" /></template>
