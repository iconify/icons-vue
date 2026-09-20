<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj5a1hovj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fj5a1hovj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:service-bell-fill" /></template>
