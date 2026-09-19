<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hey2x6psv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1280,"height":1536};
const content = `<path class="hey2x6psv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:viadeo" /></template>
