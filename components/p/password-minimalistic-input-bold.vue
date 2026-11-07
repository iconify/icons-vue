<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2d8zobch.css';
import '../../css/h/h9au5exqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2d8zobch"/><path clip-rule="evenodd" class="h9au5exqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:password-minimalistic-input-bold" /></template>
