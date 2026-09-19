<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pii91ccva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pii91ccva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:martini-glass-solid" /></template>
