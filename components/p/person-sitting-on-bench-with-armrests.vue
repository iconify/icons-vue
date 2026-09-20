<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a17i5e9cv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="a17i5e9cv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-sitting-on-bench-with-armrests" /></template>
