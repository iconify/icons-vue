<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phsw2obgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phsw2obgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:time-duration-15" /></template>
