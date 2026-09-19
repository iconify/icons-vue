<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1sagoakz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a1sagoakz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:soundcloud2" /></template>
