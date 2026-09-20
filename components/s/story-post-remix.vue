<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3vg96bsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b3vg96bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:story-post-remix" /></template>
