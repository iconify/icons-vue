<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpn8i3bxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fpn8i3bxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:twitter-solid" /></template>
