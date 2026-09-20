<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2c_x7bdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2c_x7bdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:snowflake-two-tone" /></template>
