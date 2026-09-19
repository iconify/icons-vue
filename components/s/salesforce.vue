<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttdah_b7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ttdah_b7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:salesforce" /></template>
