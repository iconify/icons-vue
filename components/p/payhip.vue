<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su0grkb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="su0grkb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:payhip" /></template>
