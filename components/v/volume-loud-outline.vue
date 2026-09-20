<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quiooc0jc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="quiooc0jc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:volume-loud-outline" /></template>
