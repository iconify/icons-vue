<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi522ibcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bi522ibcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:paragraph" /></template>
