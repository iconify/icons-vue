<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2w2cs-yy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t2w2cs-yy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:story-post-solid" /></template>
