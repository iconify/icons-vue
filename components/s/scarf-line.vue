<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itm8r4buq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itm8r4buq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:scarf-line" /></template>
