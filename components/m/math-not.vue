<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzv92pz5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzv92pz5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:math-not" /></template>
