<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwv5mcces.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwv5mcces"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:okex" /></template>
