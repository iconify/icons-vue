<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg1ngf2io.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jg1ngf2io"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pen-alt-filled" /></template>
