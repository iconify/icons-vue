<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi81hpblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fi81hpblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:mobile-phone-erase" /></template>
