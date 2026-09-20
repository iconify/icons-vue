<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drlddqb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drlddqb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:record-circle-fill" /></template>
