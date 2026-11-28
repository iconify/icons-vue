<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6c7hlb1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6c7hlb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:volume-mute-solid" /></template>
