<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnbol3bel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnbol3bel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-f9-filled" /></template>
