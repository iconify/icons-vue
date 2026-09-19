<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwde-vb2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwde-vb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:soundcloud-filled" /></template>
