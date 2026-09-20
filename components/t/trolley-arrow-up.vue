<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw_nsbqvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pw_nsbqvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:trolley-arrow-up" /></template>
