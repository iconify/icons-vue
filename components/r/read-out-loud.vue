<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw7kt4bju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qw7kt4bju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:read-out-loud" /></template>
