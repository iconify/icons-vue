<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upgfzx9xw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upgfzx9xw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:quadcopter" /></template>
