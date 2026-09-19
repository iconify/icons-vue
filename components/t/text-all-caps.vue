<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfkkiybgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfkkiybgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:text-all-caps" /></template>
