<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agx2cmddi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agx2cmddi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:youtube" /></template>
