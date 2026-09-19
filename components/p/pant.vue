<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czvroobwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":520};
const content = `<path class="czvroobwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:pant" /></template>
