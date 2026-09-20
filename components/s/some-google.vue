<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcibg-4yl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcibg-4yl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:some-google" /></template>
