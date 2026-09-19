<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oonyl_b5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":897};
const content = `<path class="oonyl_b5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:tshirt" /></template>
