<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq6c8dbwk.css';
import '../../css/p/pfp9-dnkq.css';
import '../../css/o/o2vee8t7p.css';
import '../../css/m/mzfoi9l1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gq6c8dbwk"/><path class="pfp9-dnkq"/><path class="o2vee8t7p"/><path clip-rule="evenodd" class="mzfoi9l1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:send-twice-square-outline" /></template>
