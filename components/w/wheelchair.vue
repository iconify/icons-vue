<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibfstgbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibfstgbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:wheelchair" /></template>
