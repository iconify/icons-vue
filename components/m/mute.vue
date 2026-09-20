<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6vnyqb9w.css';
import '../../css/w/wk8vleb1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6vnyqb9w"/><path class="wk8vleb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mute" /></template>
