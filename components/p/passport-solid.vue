<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgotghbbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgotghbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:passport-solid" /></template>
