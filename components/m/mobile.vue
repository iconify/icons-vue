<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q55j-hbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1280};
const content = `<path class="q55j-hbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:mobile" /></template>
