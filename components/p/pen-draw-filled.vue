<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb5j8cb2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rb5j8cb2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pen-draw-filled" /></template>
