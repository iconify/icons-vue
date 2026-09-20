<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrc4pogtw.css';
import '../../css/y/yof-aacxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrc4pogtw"/><path class="yof-aacxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:wifi" /></template>
