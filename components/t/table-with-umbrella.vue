<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6h8cybhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="o6h8cybhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:table-with-umbrella" /></template>
