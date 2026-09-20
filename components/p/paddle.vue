<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxwfs3h9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxwfs3h9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:paddle" /></template>
