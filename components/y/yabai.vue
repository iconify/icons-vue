<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irbpn6bee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irbpn6bee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:yabai" /></template>
