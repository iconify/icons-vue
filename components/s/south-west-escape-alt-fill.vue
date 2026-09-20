<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6wlk20vg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o6wlk20vg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:south-west-escape-alt-fill" /></template>
