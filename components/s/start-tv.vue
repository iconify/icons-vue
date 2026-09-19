<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1dcy4ovx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1dcy4ovx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:start-tv" /></template>
