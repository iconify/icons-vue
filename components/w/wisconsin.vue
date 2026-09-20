<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1qmgcclw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r1qmgcclw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wisconsin" /></template>
