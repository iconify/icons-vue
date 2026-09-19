<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrz_pqblx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="rrz_pqblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:teamcity" /></template>
