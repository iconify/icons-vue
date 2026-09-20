<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpbk9tr-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpbk9tr-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:ship-wheel-solid" /></template>
