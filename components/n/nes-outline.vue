<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgyosfdwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sgyosfdwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:nes-outline" /></template>
