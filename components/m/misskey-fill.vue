<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw3otxbmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aw3otxbmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:misskey-fill" /></template>
