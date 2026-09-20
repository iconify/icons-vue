<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b73v1dh2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b73v1dh2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:user-single-neutral-male-remix" /></template>
