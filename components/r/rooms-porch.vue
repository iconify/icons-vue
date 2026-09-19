<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyayz6bel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nyayz6bel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:rooms-porch" /></template>
