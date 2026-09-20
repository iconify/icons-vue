<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwle1tbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rwle1tbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:wave-pulse" /></template>
