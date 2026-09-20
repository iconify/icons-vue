<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-vaqr2yv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-vaqr2yv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:subaru" /></template>
