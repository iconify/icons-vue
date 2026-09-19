<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1bus9b3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1bus9b3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:text-number-sign" /></template>
