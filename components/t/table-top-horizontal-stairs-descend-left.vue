<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzk9z5ksk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="hzk9z5ksk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:table-top-horizontal-stairs-descend-left" /></template>
