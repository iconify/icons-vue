<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7lp9dbvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-1,"top":-3};
const content = `<path class="u7lp9dbvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:volume-mute" /></template>
