<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejhk40bjj.css';
import '../../css/f/fg50i1ydo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ejhk40bjj"/><path class="fg50i1ydo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:vertical-axis-turbine-20-bold" /></template>
