<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixs07e3on.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixs07e3on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:services" /></template>
