<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe5b5hnci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pe5b5hnci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:vultr" /></template>
