<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfqbdib-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zfqbdib-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:subdirectory-left" /></template>
