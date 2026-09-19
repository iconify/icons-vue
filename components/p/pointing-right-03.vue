<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4owv6bfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4owv6bfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pointing-right-03" /></template>
