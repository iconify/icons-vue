<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gokaoir5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gokaoir5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:restaurant" /></template>
