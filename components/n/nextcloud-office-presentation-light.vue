<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aj1gwlbyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aj1gwlbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloud-office-presentation-light" /></template>
