<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee10w_8jp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ee10w_8jp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-nine-plus-circle" /></template>
