<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ag3oe707j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ag3oe707j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:phone-top-right-with-exclamation-point" /></template>
