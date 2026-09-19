<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ip2eoqmfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ip2eoqmfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:swap-vertical" /></template>
