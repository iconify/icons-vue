<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-nb7lr8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-nb7lr8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ocean-level-rise" /></template>
