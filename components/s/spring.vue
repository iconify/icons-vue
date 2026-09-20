<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brs95qb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="brs95qb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:spring" /></template>
