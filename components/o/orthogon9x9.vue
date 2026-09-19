<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de3s681aw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="de3s681aw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:orthogon9x9" /></template>
