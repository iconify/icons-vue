<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6feaxw3l.css';
import '../../css/g/gx0j_wt-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w6feaxw3l"/><path class="gx0j_wt-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:media-library-filled" /></template>
