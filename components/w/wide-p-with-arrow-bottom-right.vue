<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4c_akmqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="p4c_akmqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wide-p-with-arrow-bottom-right" /></template>
