<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_c5a5b4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="b_c5a5b4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:rename" /></template>
