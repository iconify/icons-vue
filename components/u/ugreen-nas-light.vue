<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b76t4jl9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b76t4jl9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ugreen-nas-light" /></template>
