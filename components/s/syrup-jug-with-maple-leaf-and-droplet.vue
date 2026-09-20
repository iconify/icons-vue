<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz5xp2bca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nz5xp2bca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:syrup-jug-with-maple-leaf-and-droplet" /></template>
