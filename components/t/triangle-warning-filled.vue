<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/du6iv0jkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="du6iv0jkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:triangle-warning-filled" /></template>
