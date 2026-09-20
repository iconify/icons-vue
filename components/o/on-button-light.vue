<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q63kxsb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q63kxsb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:on-button-light" /></template>
