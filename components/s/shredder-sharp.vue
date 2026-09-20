<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgv48hb8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgv48hb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shredder-sharp" /></template>
