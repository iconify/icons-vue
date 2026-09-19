<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5hl6bc3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":488};
const content = `<path class="j5hl6bc3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:slashdot" /></template>
