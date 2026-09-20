<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efgr_ey8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="efgr_ey8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:ubuntu" /></template>
