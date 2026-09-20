<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax7wgjbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ax7wgjbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:person-off-outline" /></template>
