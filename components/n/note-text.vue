<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdxusgbcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdxusgbcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:note-text" /></template>
