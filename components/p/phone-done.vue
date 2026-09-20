<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4lmm058d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4lmm058d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:phone-done" /></template>
