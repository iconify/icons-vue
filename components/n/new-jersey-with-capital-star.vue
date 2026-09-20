<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ast8-dbzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ast8-dbzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:new-jersey-with-capital-star" /></template>
