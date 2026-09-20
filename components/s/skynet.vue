<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwj19gb-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwj19gb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:skynet" /></template>
