<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm9vkrxjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pm9vkrxjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:smoothcomp" /></template>
