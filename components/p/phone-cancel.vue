<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0tgn1auk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0tgn1auk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:phone-cancel" /></template>
