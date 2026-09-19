<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk69anb3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yk69anb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:paperclip" /></template>
