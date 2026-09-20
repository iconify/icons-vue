<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k78ok_bfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k78ok_bfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:share" /></template>
