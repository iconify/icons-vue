<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxm1gvbss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxm1gvbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:refresh-alert-solid" /></template>
