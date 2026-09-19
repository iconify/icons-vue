<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0wi9bbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="l0wi9bbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:pin-slash" /></template>
