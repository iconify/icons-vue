<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1ofg2bcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1ofg2bcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:menu-alt-3" /></template>
