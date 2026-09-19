<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3y28o36k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p3y28o36k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:user-settings-solid" /></template>
