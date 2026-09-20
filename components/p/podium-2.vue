<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_nh699rd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_nh699rd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:podium-2" /></template>
