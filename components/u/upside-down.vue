<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pju9q-5bg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pju9q-5bg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:upside-down" /></template>
