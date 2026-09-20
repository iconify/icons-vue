<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nac6i9phy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nac6i9phy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:mirroring-screen-filled" /></template>
