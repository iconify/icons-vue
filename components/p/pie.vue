<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owmn6gbht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="owmn6gbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:pie" /></template>
