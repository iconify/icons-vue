<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd9qg0nen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nd9qg0nen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:phone-16-solid" /></template>
