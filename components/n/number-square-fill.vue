<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnaxm_n2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="nnaxm_n2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:number-square-fill" /></template>
