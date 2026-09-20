<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpryc-bcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpryc-bcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ulule" /></template>
