<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgq30ub0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary zgq30ub0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:regex-duotone" /></template>
