<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jprajcb5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jprajcb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mars" /></template>
