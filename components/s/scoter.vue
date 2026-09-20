<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyuwcobdj.css';
import '../../css/n/n6xp_z95z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cyuwcobdj"/><path class="n6xp_z95z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:scoter" /></template>
