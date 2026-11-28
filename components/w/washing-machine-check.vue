<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkrydlb6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkrydlb6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:washing-machine-check" /></template>
