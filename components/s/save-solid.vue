<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh06ukb7c.css';
import '../../css/c/c3i4qtosu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uh06ukb7c"/><path class="c3i4qtosu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:save-solid" /></template>
