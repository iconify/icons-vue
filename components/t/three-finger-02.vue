<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/webyvtyva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="webyvtyva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:three-finger-02" /></template>
