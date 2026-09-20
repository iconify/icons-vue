<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhtex-0zk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhtex-0zk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-97-small" /></template>
