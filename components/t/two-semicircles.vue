<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/na-6mk1vc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="na-6mk1vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:two-semicircles" /></template>
