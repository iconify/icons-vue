<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zci8y-jwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zci8y-jwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:statue" /></template>
