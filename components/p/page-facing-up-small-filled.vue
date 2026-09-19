<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp-haacza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="tp-haacza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:page-facing-up-small-filled" /></template>
