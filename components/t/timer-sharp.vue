<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9d4z_blx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9d4z_blx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:timer-sharp" /></template>
