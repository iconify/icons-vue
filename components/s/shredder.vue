<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt48vybvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lt48vybvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:shredder" /></template>
