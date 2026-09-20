<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3jv8dbwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s3jv8dbwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:oval-broadleaved-tree-beside-oval-broadleaved-tree-on-ground" /></template>
