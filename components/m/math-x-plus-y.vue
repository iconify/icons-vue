<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/suj-smbnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="suj-smbnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:math-x-plus-y" /></template>
