<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1o-tc_3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1o-tc_3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:save-outline" /></template>
