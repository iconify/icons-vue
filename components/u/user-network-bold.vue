<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3al76g9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3al76g9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:user-network-bold" /></template>
