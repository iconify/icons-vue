<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2lntcw0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="y2lntcw0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:question-diamond-fill" /></template>
