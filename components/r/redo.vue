<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmcal6b7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmcal6b7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:redo" /></template>
