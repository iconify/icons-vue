<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8zxe7biw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m8zxe7biw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:snowflake" /></template>
