<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5yr6acra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p5yr6acra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:text-align-center" /></template>
