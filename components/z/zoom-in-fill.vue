<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbl-9e6zb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbl-9e6zb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:zoom-in-fill" /></template>
