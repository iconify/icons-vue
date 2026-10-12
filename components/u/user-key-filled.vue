<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_0m6ybdy.css';
import '../../css/s/s2joibctc.css';
import '../../css/w/wtr3z9boz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_0m6ybdy"/><path clip-rule="evenodd" class="s2joibctc"/><path class="wtr3z9boz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-key-filled" /></template>
