<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knztfskjt.css';
import '../../css/p/p-38xzm7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="knztfskjt"/><path class="p-38xzm7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ticc-dash" /></template>
