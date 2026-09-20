<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hee5pyz_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hee5pyz_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:sms" /></template>
