<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q02zdvp7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q02zdvp7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:niconico" /></template>
