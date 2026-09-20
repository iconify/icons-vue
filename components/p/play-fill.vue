<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spc0k281n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spc0k281n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:play-fill" /></template>
