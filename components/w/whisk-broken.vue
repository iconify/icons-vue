<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dji50-e4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dji50-e4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:whisk-broken" /></template>
