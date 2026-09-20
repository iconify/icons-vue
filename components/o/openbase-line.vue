<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fykk7usst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fykk7usst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:openbase-line" /></template>
