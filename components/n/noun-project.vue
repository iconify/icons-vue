<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lky9-3e9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lky9-3e9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:noun-project" /></template>
