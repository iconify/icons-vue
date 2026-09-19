<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5pyydzvd.css';
import '../../css/w/w_gpdib1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="q5pyydzvd"/><path class="w_gpdib1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:proxmox-wordmark" /></template>
