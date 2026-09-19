<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxd94ib7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":31,"height":24};
const content = `<path class="xxd94ib7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:volume-down" /></template>
