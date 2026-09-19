<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r39wynb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="r39wynb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:star-circle-fill" /></template>
