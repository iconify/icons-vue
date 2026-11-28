<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlrspib7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hlrspib7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:pizza" /></template>
