<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn2reo3hk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="pn2reo3hk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:save" /></template>
