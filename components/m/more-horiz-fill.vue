<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1_f-bgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bc1_f-bgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:more-horiz-fill" /></template>
