<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o75382b6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o75382b6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:opentf" /></template>
