<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzg21tuzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzg21tuzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:questionnaire-line" /></template>
