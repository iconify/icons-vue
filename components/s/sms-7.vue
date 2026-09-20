<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8oopqbuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a8oopqbuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:sms-7" /></template>
