<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz70ulbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fz70ulbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:open-book-in-eaved-gabled-building" /></template>
