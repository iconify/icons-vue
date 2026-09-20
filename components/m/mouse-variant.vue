<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duh40pb1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duh40pb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:mouse-variant" /></template>
