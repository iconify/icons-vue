<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srzis3ldt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="srzis3ldt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:memorial-stone-with-quaker-star" /></template>
