<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn7ih8b2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yn7ih8b2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shield-alert-solid" /></template>
