<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o79_g8b7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o79_g8b7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:moqups" /></template>
