<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iowhspbon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":280,"height":512};
const content = `<path class="iowhspbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:snyk" /></template>
