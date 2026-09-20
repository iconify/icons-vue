<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4lk5fbgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4lk5fbgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:run-fill" /></template>
