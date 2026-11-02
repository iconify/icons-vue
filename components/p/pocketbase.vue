<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhq98f3wf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="lhq98f3wf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:pocketbase" /></template>
