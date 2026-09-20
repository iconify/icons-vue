<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sl26hdf4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sl26hdf4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:rail-15" /></template>
