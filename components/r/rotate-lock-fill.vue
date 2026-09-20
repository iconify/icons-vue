<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4zw4yxvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4zw4yxvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:rotate-lock-fill" /></template>
