<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er2h4db9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="er2h4db9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:signal-circle-filled" /></template>
