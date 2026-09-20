<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5_fg5bgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a5_fg5bgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:user-identifier-card-remix" /></template>
