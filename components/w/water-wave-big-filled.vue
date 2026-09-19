<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdkoudboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdkoudboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:water-wave-big-filled" /></template>
