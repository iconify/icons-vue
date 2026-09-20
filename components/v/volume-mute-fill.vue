<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bafyibbph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bafyibbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:volume-mute-fill" /></template>
