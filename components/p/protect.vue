<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae3981pxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ae3981pxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:protect" /></template>
