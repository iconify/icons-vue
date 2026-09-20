<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/milj044hn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="milj044hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:peace-sign" /></template>
