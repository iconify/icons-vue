<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qg8l-sbko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qg8l-sbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-one-box-outline" /></template>
