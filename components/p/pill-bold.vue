<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl_-elx9a.css';
import '../../css/k/ky59n46dp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl_-elx9a"/><path class="ky59n46dp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pill-bold" /></template>
