<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/faij0bcgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="faij0bcgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:steamworks" /></template>
