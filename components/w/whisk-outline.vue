<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6ow-cbfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n6ow-cbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:whisk-outline" /></template>
