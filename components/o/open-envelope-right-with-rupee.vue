<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-qhtt8zp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s-qhtt8zp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:open-envelope-right-with-rupee" /></template>
