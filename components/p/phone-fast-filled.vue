<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-s69c4hn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-s69c4hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:phone-fast-filled" /></template>
