<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zaumeeb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zaumeeb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:table-fill-20" /></template>
