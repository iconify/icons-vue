<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3buq2dzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="s3buq2dzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:square-virus" /></template>
