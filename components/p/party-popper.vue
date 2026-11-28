<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt2wyfadz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bt2wyfadz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:party-popper" /></template>
