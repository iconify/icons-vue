<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3bsh8t5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3bsh8t5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-3-small" /></template>
