<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jf8yy7bfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jf8yy7bfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:smart-speaker2" /></template>
