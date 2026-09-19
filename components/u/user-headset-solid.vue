<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwbmpddhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rwbmpddhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:user-headset-solid" /></template>
