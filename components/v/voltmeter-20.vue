<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8zyk_juu.css';
import '../../css/b/bhtgracju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e8zyk_juu"/><path class="bhtgracju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:voltmeter-20" /></template>
