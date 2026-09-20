<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmyt9bbit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmyt9bbit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:timer-fill" /></template>
