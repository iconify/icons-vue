<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/aw-cmtbxz.css';
import '../../css/u/u3qkv6btp.css';
import '../../css/s/smde8tpuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="aw-cmtbxz"/><path class="u3qkv6btp"/><path class="smde8tpuu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:skull" /></template>
