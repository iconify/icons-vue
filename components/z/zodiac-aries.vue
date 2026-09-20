<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7kfprb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7kfprb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:zodiac-aries" /></template>
