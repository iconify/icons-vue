<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp0hrebwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hp0hrebwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:network-strength-3" /></template>
