<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md9mqdmzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="md9mqdmzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:umbrella-solid" /></template>
