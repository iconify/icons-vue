<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh_8zbb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eh_8zbb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:map-pin-alt-solid" /></template>
