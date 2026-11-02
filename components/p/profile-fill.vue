<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtwsf5ntq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtwsf5ntq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:profile-fill" /></template>
