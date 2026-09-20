<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5m1qigkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t5m1qigkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pill-bottle" /></template>
