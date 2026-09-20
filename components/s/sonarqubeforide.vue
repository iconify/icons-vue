<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqq5v3bjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqq5v3bjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:sonarqubeforide" /></template>
