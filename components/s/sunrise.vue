<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zeqprcb2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="zeqprcb2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:sunrise" /></template>
