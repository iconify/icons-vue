<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez0wvl5yk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ez0wvl5yk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:nature-outline" /></template>
