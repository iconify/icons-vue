<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sl19-4ccv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sl19-4ccv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:on-sight" /></template>
