<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bijlm4yyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bijlm4yyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:xbox-controller-battery-charging" /></template>
