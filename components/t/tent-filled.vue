<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_lop9b3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_lop9b3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:tent-filled" /></template>
