<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr8zurb6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pr8zurb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:pbs-kids-alt" /></template>
