<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn26v467x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sn26v467x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vanity-light" /></template>
