<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpan3nb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpan3nb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:phone" /></template>
