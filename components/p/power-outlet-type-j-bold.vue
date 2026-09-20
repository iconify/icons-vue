<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3as_xbml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y3as_xbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:power-outlet-type-j-bold" /></template>
