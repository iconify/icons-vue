<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqgumy6mn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="bqgumy6mn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:table-badge-more-fill" /></template>
