<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk41io1ew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mk41io1ew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:teddy-bear-solid" /></template>
