<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy_wbc1rc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="zy_wbc1rc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:web-template" /></template>
