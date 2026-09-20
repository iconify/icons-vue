<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd2ny6bnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jd2ny6bnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:party-decoration-bold" /></template>
