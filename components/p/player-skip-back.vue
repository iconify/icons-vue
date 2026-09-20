<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4hwofa_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4hwofa_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:player-skip-back" /></template>
