<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyvcxbgtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wyvcxbgtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:power-outlet-type-f-bold" /></template>
