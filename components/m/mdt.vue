<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdoiz26ay.css';
import '../../css/t/tc6em5bpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdoiz26ay"/><path class="tc6em5bpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mdt" /></template>
