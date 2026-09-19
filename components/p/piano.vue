<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_xjfiztf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":961,"height":1024};
const content = `<path class="h_xjfiztf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:piano" /></template>
