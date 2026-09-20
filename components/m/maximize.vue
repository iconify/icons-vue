<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdk9i9par.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdk9i9par"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:maximize" /></template>
