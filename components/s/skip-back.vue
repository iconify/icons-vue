<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao2o_1coz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ao2o_1coz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:skip-back" /></template>
