<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aod_41bqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="aod_41bqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:podcast" /></template>
