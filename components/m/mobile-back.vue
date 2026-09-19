<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ul4ei0bva.css';
import '../../css/s/sqg9nvbrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ul4ei0bva"/><path class="sqg9nvbrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:mobile-back" /></template>
