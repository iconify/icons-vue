<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwjddt0wq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xwjddt0wq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:tag-filled" /></template>
