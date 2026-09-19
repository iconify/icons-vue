<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysjxyibud.css';
import '../../css/h/hipmx6vje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysjxyibud"/><path class="hipmx6vje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:vignette" /></template>
