<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftce25oby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftce25oby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:medium-filled" /></template>
