<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zheuj0y8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zheuj0y8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-hanging-from-horizontal-bar" /></template>
