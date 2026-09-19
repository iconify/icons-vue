<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btttoqbuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btttoqbuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:typescript" /></template>
