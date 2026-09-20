<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm066d1jb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tm066d1jb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloud-deck-light" /></template>
