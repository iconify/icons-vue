<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm4bagw4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rm4bagw4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:other-2-outline" /></template>
