<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwwv59bwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":520};
const content = `<path class="zwwv59bwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:shield" /></template>
