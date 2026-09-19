<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ege3f6bdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ege3f6bdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:notice-on" /></template>
