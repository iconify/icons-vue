<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb4ip3btx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="nb4ip3btx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:navigate-back" /></template>
