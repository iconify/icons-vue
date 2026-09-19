<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc28kmb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="lc28kmb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:squares-2x2-20-solid" /></template>
