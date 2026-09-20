<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg3giegrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fg3giegrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:polygon" /></template>
