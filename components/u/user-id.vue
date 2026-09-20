<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1x756bcr.css';
import '../../css/a/av7mo7pep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1x756bcr"/><path class="av7mo7pep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:user-id" /></template>
