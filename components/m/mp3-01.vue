<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gczf5uo1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gczf5uo1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mp3-01" /></template>
