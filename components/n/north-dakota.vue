<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3s3fb6sn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g3s3fb6sn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:north-dakota" /></template>
