<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-4or8fvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-4or8fvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:surround-sound-2-1" /></template>
