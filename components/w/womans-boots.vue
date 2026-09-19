<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rravu28bc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="rravu28bc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:womans-boots" /></template>
