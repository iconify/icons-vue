<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl7z0xbvn.css';
import '../../css/y/y07exzb3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nl7z0xbvn"/><path class="y07exzb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:notepad" /></template>
