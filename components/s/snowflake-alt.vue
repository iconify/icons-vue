<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg3rv6t7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg3rv6t7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:snowflake-alt" /></template>
