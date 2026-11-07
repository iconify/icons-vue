<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp6su4bex.css';
import '../../css/p/potfbbb8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yp6su4bex"/><path clip-rule="evenodd" class="potfbbb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mention-circle-bold" /></template>
