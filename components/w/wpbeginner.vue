<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdd9zacpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jdd9zacpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:wpbeginner" /></template>
