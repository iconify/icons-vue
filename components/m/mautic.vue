<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2blzpbts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2blzpbts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:mautic" /></template>
