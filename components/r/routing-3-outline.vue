<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of9ozfbbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="of9ozfbbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:routing-3-outline" /></template>
