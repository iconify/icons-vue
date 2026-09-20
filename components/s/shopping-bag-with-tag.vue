<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvml22e6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tvml22e6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:shopping-bag-with-tag" /></template>
