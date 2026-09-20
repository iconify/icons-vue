<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_rqqg3ll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b_rqqg3ll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:spiky-fish-under-paragraph" /></template>
