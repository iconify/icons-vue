<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2-777_wb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="z2-777_wb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:placard-small" /></template>
