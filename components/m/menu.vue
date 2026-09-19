<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbh6_gbph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbh6_gbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:menu" /></template>
