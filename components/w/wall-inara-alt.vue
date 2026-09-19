<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cx6u9sb_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cx6u9sb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:wall-inara-alt" /></template>
