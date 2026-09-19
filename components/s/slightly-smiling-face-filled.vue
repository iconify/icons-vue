<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr6m2nb0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="tr6m2nb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:slightly-smiling-face-filled" /></template>
