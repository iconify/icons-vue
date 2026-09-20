<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpn8ptbkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpn8ptbkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-x-sharp" /></template>
