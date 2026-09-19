<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvoxqobib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvoxqobib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:user-plus-filled" /></template>
