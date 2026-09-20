<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1dh4bbcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f1dh4bbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:shopping-bag-with-leaf" /></template>
