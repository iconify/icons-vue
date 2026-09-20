<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-gr9vbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-gr9vbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:synchronize-arrows-three-bold" /></template>
