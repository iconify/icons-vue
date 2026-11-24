<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfctapahl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfctapahl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:toothbrush-sparkles-filled" /></template>
