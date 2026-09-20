<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erdpm_zyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="erdpm_zyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:spacing-large-24" /></template>
