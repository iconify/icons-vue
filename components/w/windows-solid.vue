<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f21hec9sg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f21hec9sg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:windows-solid" /></template>
