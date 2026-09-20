<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swew10n1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="swew10n1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:table-top-door-horizontal" /></template>
