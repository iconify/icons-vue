<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpz043b_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zpz043b_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wall-tent" /></template>
