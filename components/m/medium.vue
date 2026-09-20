<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu7-xr7bm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lu7-xr7bm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:medium" /></template>
