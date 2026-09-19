<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olk0odbzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="olk0odbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:user-police" /></template>
