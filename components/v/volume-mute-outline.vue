<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-8v07bmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-8v07bmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:volume-mute-outline" /></template>
