<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozp9g2b1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ozp9g2b1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:server-solid" /></template>
