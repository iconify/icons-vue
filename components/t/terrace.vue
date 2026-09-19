<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvj62rbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvj62rbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:terrace" /></template>
