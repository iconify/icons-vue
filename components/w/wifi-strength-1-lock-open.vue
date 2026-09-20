<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eafz5sbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eafz5sbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wifi-strength-1-lock-open" /></template>
