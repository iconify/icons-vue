<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi6ik7bvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pi6ik7bvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:th" /></template>
