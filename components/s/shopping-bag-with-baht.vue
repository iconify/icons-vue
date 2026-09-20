<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enltw_b2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="enltw_b2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:shopping-bag-with-baht" /></template>
