<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hst90xz2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hst90xz2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:repeat-alt" /></template>
