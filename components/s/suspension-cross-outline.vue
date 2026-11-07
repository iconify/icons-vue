<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t25cvmbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t25cvmbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:suspension-cross-outline" /></template>
