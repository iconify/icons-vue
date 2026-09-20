<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqiu6pb8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bqiu6pb8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:yugabytedb" /></template>
