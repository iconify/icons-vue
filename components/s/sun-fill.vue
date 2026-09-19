<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bz6p9kmmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bz6p9kmmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:sun-fill" /></template>
