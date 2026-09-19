<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crub4ucgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crub4ucgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:minus-outline" /></template>
