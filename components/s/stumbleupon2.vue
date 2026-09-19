<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xoh4y3b0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xoh4y3b0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:stumbleupon2" /></template>
