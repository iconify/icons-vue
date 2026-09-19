<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzzxcnbde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pzzxcnbde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:thumbtack-diagonal" /></template>
