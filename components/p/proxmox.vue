<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uau7xsbht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="uau7xsbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:proxmox" /></template>
