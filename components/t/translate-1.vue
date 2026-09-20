<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqj6kbgeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqj6kbgeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:translate-1" /></template>
