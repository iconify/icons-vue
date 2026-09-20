<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze9lr2bnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ze9lr2bnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:padlock-square-1-remix" /></template>
