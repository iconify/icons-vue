<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w__oz7bxg.css';
import '../../css/k/k_lqyobox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w__oz7bxg"/><path class="k_lqyobox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:message-dots" /></template>
