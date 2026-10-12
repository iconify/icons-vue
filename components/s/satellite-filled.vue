<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8furxbvt.css';
import '../../css/o/oe3ikkuio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8furxbvt"/><path clip-rule="evenodd" class="oe3ikkuio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:satellite-filled" /></template>
