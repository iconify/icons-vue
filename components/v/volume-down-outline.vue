<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlrf9sb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qlrf9sb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:volume-down-outline" /></template>
