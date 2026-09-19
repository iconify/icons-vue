<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3c-h0b4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="s3c-h0b4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pigpeni" /></template>
