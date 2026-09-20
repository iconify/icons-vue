<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz6v6hiby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz6v6hiby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:phone-outgoing" /></template>
