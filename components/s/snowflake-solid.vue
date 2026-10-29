<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6q3n9bvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6q3n9bvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:snowflake-solid" /></template>
