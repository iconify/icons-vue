<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6zmvbcdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":717};
const content = `<path class="u6zmvbcdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:picasa" /></template>
