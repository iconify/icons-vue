<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iycazvbqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2624,"height":2016};
const content = `<path class="iycazvbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:people-group" /></template>
