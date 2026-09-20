<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tubgozbzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tubgozbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-98-small" /></template>
