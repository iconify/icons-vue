<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1l7e8acw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1l7e8acw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:slash-square-solid" /></template>
