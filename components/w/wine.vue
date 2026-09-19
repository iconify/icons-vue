<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2_fs0idi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":23,"height":32};
const content = `<path class="y2_fs0idi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:wine" /></template>
