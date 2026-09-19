<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj9q7uu1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rj9q7uu1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:stage-spot-light" /></template>
