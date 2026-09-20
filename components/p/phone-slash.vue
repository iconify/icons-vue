<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_afapeoj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f_afapeoj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:phone-slash" /></template>
