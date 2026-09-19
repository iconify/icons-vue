<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6aazewdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6aazewdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:petrol-pump" /></template>
