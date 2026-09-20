<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-o_25boi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="o-o_25boi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:paintbrush-solid" /></template>
