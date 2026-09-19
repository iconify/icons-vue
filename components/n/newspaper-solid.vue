<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i566vrbpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i566vrbpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:newspaper-solid" /></template>
