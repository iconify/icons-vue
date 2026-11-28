<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6c_n6ydo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary q6c_n6ydo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:toothbrush-duotone" /></template>
