<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssa9kaq0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ssa9kaq0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:openal" /></template>
