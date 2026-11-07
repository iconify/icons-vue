<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l10h6cbda.css';
import '../../css/y/yv3sgvbaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l10h6cbda"/><path clip-rule="evenodd" class="yv3sgvbaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:stretching-bold" /></template>
