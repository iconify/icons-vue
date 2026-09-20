<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nggnj1poa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nggnj1poa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:recycle-1-solid" /></template>
