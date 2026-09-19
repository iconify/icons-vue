<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8htchb6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8htchb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:note" /></template>
