<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1ctmb3bg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1ctmb3bg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:royalty" /></template>
