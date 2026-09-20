<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b59ndpb0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b59ndpb0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:rocket-2" /></template>
