<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itl9s5g-p.css';
import '../../css/z/z6pxdsb4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itl9s5g-p"/><path class="z6pxdsb4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:spa-filled" /></template>
