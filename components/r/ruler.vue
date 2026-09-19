<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bulg0db2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="bulg0db2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:ruler" /></template>
