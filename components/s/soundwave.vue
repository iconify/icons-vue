<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_sqc-bvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p_sqc-bvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:soundwave" /></template>
