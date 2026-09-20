<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzsqa9bwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzsqa9bwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ship-sharp" /></template>
