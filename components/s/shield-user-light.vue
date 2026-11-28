<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hykce9b8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="hykce9b8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:shield-user-light" /></template>
