<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbl53bb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbl53bb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:squares-subtract-filled" /></template>
