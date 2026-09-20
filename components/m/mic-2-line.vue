<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wo3caibxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wo3caibxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mic-2-line" /></template>
