<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehsl2h5wv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ehsl2h5wv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:subscript" /></template>
