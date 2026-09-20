<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj-a1cb1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qj-a1cb1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:snowflake-sharp-fill" /></template>
