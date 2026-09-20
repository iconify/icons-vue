<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpayq2cbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gpayq2cbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:osu" /></template>
