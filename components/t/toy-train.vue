<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/e/ec_xsy4gs.css';
import '../../css/b/bf9hqaclw.css';
import '../../css/a/az8wk3mni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ec_xsy4gs"/><circle class="bf9hqaclw"/><path class="az8wk3mni"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:toy-train" /></template>
