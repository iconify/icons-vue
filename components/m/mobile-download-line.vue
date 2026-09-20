<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/neebi438u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="neebi438u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mobile-download-line" /></template>
