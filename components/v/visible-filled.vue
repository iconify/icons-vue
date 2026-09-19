<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uacxlzfww.css';
import '../../css/j/j0vie5bjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uacxlzfww"/><path clip-rule="evenodd" class="j0vie5bjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:visible-filled" /></template>
