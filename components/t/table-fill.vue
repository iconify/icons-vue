<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdpbjcvcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="jdpbjcvcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:table-fill" /></template>
