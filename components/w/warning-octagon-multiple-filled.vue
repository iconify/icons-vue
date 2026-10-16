<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddqgvxbqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddqgvxbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:warning-octagon-multiple-filled" /></template>
