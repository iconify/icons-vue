<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbe9ikuca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbe9ikuca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:rectangle" /></template>
