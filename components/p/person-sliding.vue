<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv94sthss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qv94sthss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-sliding" /></template>
