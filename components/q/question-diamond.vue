<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb1q2tp7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="cb1q2tp7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:question-diamond" /></template>
