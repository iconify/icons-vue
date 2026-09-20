<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aytm96b7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aytm96b7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pot-steam-outline" /></template>
