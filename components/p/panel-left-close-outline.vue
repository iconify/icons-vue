<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahcs-h-rh.css';
import '../../css/f/fzr5emvaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahcs-h-rh"/><path clip-rule="evenodd" class="fzr5emvaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panel-left-close-outline" /></template>
