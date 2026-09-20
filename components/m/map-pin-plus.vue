<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scj2mpbxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scj2mpbxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:map-pin-plus" /></template>
