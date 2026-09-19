<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_v_5prdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_v_5prdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:sunrise" /></template>
