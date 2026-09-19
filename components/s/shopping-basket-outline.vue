<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfdvjkbvs.css';
import '../../css/c/c6rg3sbah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfdvjkbvs"/><path clip-rule="evenodd" class="c6rg3sbah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:shopping-basket-outline" /></template>
