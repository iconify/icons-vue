<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2ob-jb0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2ob-jb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:tab-plus" /></template>
