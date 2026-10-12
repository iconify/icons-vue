<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti93n7b7m.css';
import '../../css/u/u2_dmwbyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ti93n7b7m"/><path class="u2_dmwbyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mouse-right-filled" /></template>
