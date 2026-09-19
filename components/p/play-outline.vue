<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ga28a4bip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ga28a4bip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:play-outline" /></template>
