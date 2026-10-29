<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm2qkko-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tm2qkko-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:shredder" /></template>
