<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhl3z13hj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="vhl3z13hj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:mark-down-language" /></template>
