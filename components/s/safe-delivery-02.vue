<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5oymmblr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5oymmblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:safe-delivery-02" /></template>
