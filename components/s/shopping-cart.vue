<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1r3f5ojh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b1r3f5ojh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:shopping-cart" /></template>
