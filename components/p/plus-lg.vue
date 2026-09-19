<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0j119nmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h0j119nmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:plus-lg" /></template>
