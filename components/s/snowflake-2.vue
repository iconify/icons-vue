<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5vuvxbox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":23,"height":24};
const content = `<path class="f5vuvxbox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:snowflake-2" /></template>
