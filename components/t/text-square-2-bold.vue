<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulv-w-b-t.css';
import '../../css/m/m6ejkju0k.css';
import '../../css/m/mv3shgefo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ulv-w-b-t"/><path class="m6ejkju0k"/><path class="mv3shgefo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-square-2-bold" /></template>
