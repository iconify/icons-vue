<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzml9mbbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tzml9mbbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:rewind-small-outline" /></template>
