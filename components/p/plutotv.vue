<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4c6_3buo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4c6_3buo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:plutotv" /></template>
