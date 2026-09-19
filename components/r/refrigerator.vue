<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vluce1bdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vluce1bdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:refrigerator" /></template>
