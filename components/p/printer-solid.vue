<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y20u0nbff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y20u0nbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:printer-solid" /></template>
