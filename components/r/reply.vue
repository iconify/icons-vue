<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx5bmgb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rx5bmgb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:reply" /></template>
