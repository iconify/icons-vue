<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlm_yccip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dlm_yccip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:piggy-bank-plus" /></template>
