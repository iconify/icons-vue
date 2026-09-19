<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5ip8yb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":420,"height":810};
const content = `<path class="r5ip8yb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:mobile" /></template>
