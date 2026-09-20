<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur361hbvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ur361hbvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:mouse-2-filled" /></template>
