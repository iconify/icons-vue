<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcdky6nmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gcdky6nmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:x-alt" /></template>
