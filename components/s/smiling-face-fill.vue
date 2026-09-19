<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omcviu_cr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omcviu_cr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:smiling-face-fill" /></template>
