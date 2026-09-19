<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z194h6bnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1408,"height":1792};
const content = `<path class="z194h6bnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:volume-control-phone" /></template>
