<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu40tbc2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wu40tbc2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:music-solid" /></template>
