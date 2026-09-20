<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_ks2lbjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_ks2lbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:snowflake-fill" /></template>
