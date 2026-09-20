<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/va1ouek0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="va1ouek0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:trashcan-solid" /></template>
