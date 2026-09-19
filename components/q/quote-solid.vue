<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imoh3dbho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="imoh3dbho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:quote-solid" /></template>
