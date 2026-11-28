<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-3sfv_0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary t-3sfv_0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:tooth-duotone" /></template>
