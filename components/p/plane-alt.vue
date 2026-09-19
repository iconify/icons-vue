<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go9r8we_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="go9r8we_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:plane-alt" /></template>
