<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y17aut7vh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y17aut7vh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:open-chest-with-treasure-and-sparkles" /></template>
