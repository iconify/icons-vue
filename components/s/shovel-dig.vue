<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z414etblc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z414etblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:shovel-dig" /></template>
