<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnwsbq4ky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnwsbq4ky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:zodiac-aries-solid" /></template>
