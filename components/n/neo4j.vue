<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkwtqebyl.css';
import '../../css/h/h08ulmihp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="dkwtqebyl"/><path class="h08ulmihp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:neo4j" /></template>
