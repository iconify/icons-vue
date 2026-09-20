<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3pummbfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u3pummbfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:oculus-logo" /></template>
