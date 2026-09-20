<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5qn0db8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l5qn0db8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:waterfall-15" /></template>
