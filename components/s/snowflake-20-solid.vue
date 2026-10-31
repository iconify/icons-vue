<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ote9-7bkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ote9-7bkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:snowflake-20-solid" /></template>
