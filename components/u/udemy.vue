<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nq4snrqik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nq4snrqik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:udemy" /></template>
