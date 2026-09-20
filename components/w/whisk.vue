<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/majbnhb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="majbnhb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:whisk" /></template>
