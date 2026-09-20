<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hoyfe3bws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hoyfe3bws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:pen-to-square" /></template>
