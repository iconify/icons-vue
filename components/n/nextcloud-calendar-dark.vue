<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptx1sh0xb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ptx1sh0xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloud-calendar-dark" /></template>
