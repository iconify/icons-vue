<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gi8h8gaxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gi8h8gaxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:powershell" /></template>
