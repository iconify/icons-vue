<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z09gg-b_z.css';
import '../../css/a/absjoyb4u.css';
import '../../css/y/y1zrpxbtp.css';
import '../../css/w/wocmnefrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z09gg-b_z"/><path class="absjoyb4u"/><path class="y1zrpxbtp"/><path clip-rule="evenodd" class="wocmnefrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:upload-track-bold" /></template>
