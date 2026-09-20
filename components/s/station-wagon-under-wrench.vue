<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2rb7ob_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b2rb7ob_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:station-wagon-under-wrench" /></template>
