<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b603scljm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b603scljm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:paperclip" /></template>
