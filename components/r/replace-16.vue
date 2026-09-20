<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/feoxutb2p.css';
import '../../css/c/ce2rhacdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="feoxutb2p"/><path class="ce2rhacdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:replace-16" /></template>
