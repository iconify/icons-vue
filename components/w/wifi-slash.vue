<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv4fwl-ev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kv4fwl-ev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:wifi-slash" /></template>
