<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p74ref19a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p74ref19a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:media-stop-outline" /></template>
