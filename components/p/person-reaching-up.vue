<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1ieycbfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="n1ieycbfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-reaching-up" /></template>
