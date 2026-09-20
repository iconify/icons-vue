<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfpc-lb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="nfpc-lb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:screen-alt-2-solid" /></template>
