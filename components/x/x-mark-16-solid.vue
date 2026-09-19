<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3p7ifb9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c3p7ifb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:x-mark-16-solid" /></template>
