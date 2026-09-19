<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bazxsibde.css';
import '../../css/r/ri5_0i_ew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bazxsibde"/><path class="ri5_0i_ew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:rotate-ccw-30-filled" /></template>
