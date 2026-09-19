<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfgfls12i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfgfls12i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sprinkler" /></template>
