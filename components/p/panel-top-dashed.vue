<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyhobybdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyhobybdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-top-dashed" /></template>
