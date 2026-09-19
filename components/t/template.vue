<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hw1zfl6mu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hw1zfl6mu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:template" /></template>
