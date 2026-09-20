<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2xlc5b-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2xlc5b-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-4-box-multiple" /></template>
