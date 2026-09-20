<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq15uw1-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="iq15uw1-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:pilcrow" /></template>
