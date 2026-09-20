<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea5ltub7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ea5ltub7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:shopping-bag-with-shekel" /></template>
