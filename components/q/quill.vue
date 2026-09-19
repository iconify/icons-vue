<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smu97hcnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="smu97hcnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:quill" /></template>
