<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz5sbl4bp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="jz5sbl4bp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:speaker-2-fill" /></template>
