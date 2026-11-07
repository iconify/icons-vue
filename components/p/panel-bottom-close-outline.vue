<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdh483e9a.css';
import '../../css/y/y-3rifbqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdh483e9a"/><path clip-rule="evenodd" class="y-3rifbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panel-bottom-close-outline" /></template>
