<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ume5d43jk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ume5d43jk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:storage" /></template>
