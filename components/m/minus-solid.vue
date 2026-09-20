<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smz97zb8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="smz97zb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:minus-solid" /></template>
