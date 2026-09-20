<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aweawcc1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aweawcc1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:person-tick-outline" /></template>
