<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_1b6abit.css';
import '../../css/z/ztdsiac1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_1b6abit"/><path class="ztdsiac1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:owl" /></template>
