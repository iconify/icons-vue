<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjd_78iqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjd_78iqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:skull-filled" /></template>
