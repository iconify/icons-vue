<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bitcrkbwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bitcrkbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:trending-down" /></template>
