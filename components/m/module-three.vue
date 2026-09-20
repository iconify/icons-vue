<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jp48ishqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jp48ishqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:module-three" /></template>
