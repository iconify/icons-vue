<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc922ob0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rc922ob0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:rye" /></template>
