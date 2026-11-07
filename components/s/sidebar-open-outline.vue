<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j21lmxkpv.css';
import '../../css/z/zueniel6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j21lmxkpv"/><path clip-rule="evenodd" class="zueniel6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sidebar-open-outline" /></template>
