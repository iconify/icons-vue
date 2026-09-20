<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv57wib5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dv57wib5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:maple-leaf" /></template>
