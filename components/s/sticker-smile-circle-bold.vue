<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezqx6dokg.css';
import '../../css/k/kmymo-b1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezqx6dokg"/><path clip-rule="evenodd" class="kmymo-b1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sticker-smile-circle-bold" /></template>
