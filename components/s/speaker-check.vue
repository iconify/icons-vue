<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1pxdb6ib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1pxdb6ib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:speaker-check" /></template>
