<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v40n-8bcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v40n-8bcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:square-library" /></template>
