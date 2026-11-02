<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpvnkvb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpvnkvb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:volume-low-fill" /></template>
