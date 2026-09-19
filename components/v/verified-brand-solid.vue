<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv46ilbby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="dv46ilbby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:verified-brand-solid" /></template>
