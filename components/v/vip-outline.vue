<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x50dklg_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x50dklg_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:vip-outline" /></template>
