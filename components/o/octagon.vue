<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la15vfbze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="la15vfbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:octagon" /></template>
