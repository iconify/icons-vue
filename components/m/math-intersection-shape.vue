<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b068bac4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b068bac4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:math-intersection-shape" /></template>
