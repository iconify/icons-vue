<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1b3226np.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1b3226np"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:pills" /></template>
