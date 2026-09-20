<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg0jpcchu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xg0jpcchu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:maximize4-filled" /></template>
