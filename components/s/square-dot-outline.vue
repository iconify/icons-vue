<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er9_2_bjd.css';
import '../../css/n/n8eavcbnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="er9_2_bjd"/><path clip-rule="evenodd" class="n8eavcbnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-dot-outline" /></template>
