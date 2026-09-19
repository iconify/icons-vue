<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r34fhinxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="r34fhinxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:tray-arrow-up-fill" /></template>
