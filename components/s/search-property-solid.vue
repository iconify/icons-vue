<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb-ftubup.css';
import '../../css/e/e3bbx6bvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kb-ftubup"/><path clip-rule="evenodd" class="e3bbx6bvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:search-property-solid" /></template>
