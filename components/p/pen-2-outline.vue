<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhnybhx3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bhnybhx3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pen-2-outline" /></template>
