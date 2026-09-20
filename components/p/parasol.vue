<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pay8v6kzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pay8v6kzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:parasol" /></template>
