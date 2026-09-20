<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htzdpg-mi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="htzdpg-mi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:two-diamond-solid" /></template>
