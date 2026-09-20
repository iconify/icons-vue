<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gk8rsab9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gk8rsab9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tangram" /></template>
