<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w__z_2btt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w__z_2btt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:text-align-right" /></template>
