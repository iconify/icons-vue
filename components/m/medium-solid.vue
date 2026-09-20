<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qya48qbrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="qya48qbrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:medium-solid" /></template>
