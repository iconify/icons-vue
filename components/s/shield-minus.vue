<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7jme086z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7jme086z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:shield-minus" /></template>
