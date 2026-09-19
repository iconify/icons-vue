<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtiocmbqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtiocmbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:microphone-slash-solid" /></template>
