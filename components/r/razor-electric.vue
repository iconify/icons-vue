<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2a02ybrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2a02ybrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:razor-electric" /></template>
