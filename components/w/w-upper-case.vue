<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er9vcipei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":888,"height":786};
const content = `<path class="er9vcipei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:w-upper-case" /></template>
