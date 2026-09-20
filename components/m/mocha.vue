<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw_sm9b6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nw_sm9b6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:mocha" /></template>
