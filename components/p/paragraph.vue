<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lglo9xbwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lglo9xbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:paragraph" /></template>
