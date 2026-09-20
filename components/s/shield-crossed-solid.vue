<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e11jas_xe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e11jas_xe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:shield-crossed-solid" /></template>
