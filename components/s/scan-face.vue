<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pumep9bwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pumep9bwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:scan-face" /></template>
