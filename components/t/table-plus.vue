<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xoyc0yn7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xoyc0yn7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:table-plus" /></template>
