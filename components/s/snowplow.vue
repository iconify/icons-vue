<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvomvxbni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="pvomvxbni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:snowplow" /></template>
