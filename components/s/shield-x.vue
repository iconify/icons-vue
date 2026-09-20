<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu4ghgmcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wu4ghgmcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shield-x" /></template>
