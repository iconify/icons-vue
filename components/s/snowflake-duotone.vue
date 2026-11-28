<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua7k72yme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary ua7k72yme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:snowflake-duotone" /></template>
