<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0l3m7e7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0l3m7e7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:shield-minus-solid" /></template>
