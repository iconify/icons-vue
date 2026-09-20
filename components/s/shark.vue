<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhdv5acbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="rhdv5acbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:shark" /></template>
