<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/du81u6b2b.css';
import '../../css/u/ut-e98spq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="du81u6b2b"/><path class="ut-e98spq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:synchronize-arrows" /></template>
