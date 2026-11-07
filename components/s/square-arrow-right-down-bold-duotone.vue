<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atpjn6hvy.css';
import '../../css/a/at2vc6bce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atpjn6hvy"/><path class="at2vc6bce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-arrow-right-down-bold-duotone" /></template>
