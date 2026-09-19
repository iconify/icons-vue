<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vba-dkb_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vba-dkb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:water-wave-big" /></template>
