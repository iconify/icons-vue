<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpus6cb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpus6cb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:progress-3-line" /></template>
