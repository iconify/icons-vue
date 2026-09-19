<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uelnaabaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uelnaabaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:user-group" /></template>
