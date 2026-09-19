<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujzt-9bwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ujzt-9bwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:megaphone-16-solid" /></template>
