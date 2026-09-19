<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac91_xbdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ac91_xbdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-5-thin" /></template>
