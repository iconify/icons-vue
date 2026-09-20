<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3o1lpb7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b3o1lpb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:mood-laugh-outline" /></template>
