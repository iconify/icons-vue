<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg261rb8a.css';
import '../../css/m/mdoipsbrh.css';
import '../../css/l/lc21qzuqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rg261rb8a"/><path clip-rule="evenodd" class="mdoipsbrh"/><path class="lc21qzuqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-heart-bold" /></template>
