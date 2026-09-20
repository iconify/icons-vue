<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai6wcvbfj.css';
import '../../css/f/fhh8osb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ai6wcvbfj"/><path class="fhh8osb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:users-solid" /></template>
