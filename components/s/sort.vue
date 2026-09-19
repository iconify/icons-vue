<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx03b9a_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zx03b9a_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:sort" /></template>
