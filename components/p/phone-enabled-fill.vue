<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sarw6hbex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sarw6hbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:phone-enabled-fill" /></template>
