<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1bxtwk9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="v1bxtwk9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:proxmox-wordmark" /></template>
