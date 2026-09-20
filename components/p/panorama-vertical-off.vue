<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwryu69jf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwryu69jf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:panorama-vertical-off" /></template>
