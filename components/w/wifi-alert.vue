<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8y2vtl5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8y2vtl5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:wifi-alert" /></template>
