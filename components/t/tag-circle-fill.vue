<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6xi21cel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="x6xi21cel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:tag-circle-fill" /></template>
