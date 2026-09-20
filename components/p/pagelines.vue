<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agbq3cbth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agbq3cbth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:pagelines" /></template>
