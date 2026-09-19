<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkfwscg9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="dkfwscg9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:player-stop-light" /></template>
