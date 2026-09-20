<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmroz-zfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmroz-zfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:plug" /></template>
