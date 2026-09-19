<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehev_nbyn.css';
import '../../css/l/l028m6bye.css';
import '../../css/f/fr-8w9hqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ehev_nbyn"/><path class="l028m6bye"/><path class="fr-8w9hqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:yaml" /></template>
