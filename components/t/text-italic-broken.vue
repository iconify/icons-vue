<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq5ja2bbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dq5ja2bbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-italic-broken" /></template>
