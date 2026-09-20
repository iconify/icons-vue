<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v08yu0bkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v08yu0bkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:wells-fargo" /></template>
