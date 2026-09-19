<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ontpq2bhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ontpq2bhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:squarem" /></template>
