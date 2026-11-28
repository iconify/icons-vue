<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg1i90eaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tg1i90eaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:radius-solid" /></template>
