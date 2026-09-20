<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cle0u0bwz.css';
import '../../css/e/e1s56dbln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cle0u0bwz"/><path class="e1s56dbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:note-24" /></template>
