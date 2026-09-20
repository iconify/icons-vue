<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcsvb_bcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mcsvb_bcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:stars-light" /></template>
