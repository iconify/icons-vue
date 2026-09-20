<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k983gnjgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k983gnjgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:some-pinterest" /></template>
