<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bch5yjxyw.css';
import '../../css/j/j6p__-b8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bch5yjxyw"/><path clip-rule="evenodd" class="j6p__-b8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:sun-filled" /></template>
