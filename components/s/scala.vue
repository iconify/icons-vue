<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brcgyim-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brcgyim-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:scala" /></template>
