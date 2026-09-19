<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xewd8ubff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":424,"height":512};
const content = `<path class="xewd8ubff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:prisma" /></template>
