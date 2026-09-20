<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/be9ptibte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="be9ptibte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:thinkpad" /></template>
