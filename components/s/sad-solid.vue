<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c43vspbra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c43vspbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:sad-solid" /></template>
