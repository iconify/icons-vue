<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lclljrq5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lclljrq5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:video" /></template>
