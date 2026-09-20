<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd6j98biy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nd6j98biy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:user-cross-fill" /></template>
