<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsz4ihbgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="dsz4ihbgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:viruses" /></template>
