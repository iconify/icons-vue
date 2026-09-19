<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2ban2-eb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="x2ban2-eb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:question-circle" /></template>
