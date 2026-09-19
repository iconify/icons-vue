<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0-onzpmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="r0-onzpmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:xmark-octagon-fill" /></template>
