<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9687bcgq.css';
import '../../css/p/po09tr52l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9687bcgq"/><path clip-rule="evenodd" class="po09tr52l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:pencil-single" /></template>
