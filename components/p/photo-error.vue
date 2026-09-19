<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrxfrs-5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="zrxfrs-5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:photo-error" /></template>
