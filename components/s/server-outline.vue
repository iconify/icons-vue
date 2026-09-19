<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2ia5obuy.css';
import '../../css/u/umym_-bpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2ia5obuy"/><path clip-rule="evenodd" class="umym_-bpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:server-outline" /></template>
