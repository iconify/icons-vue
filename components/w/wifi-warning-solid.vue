<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxznp3bar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bxznp3bar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:wifi-warning-solid" /></template>
