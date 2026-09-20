<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwwxjabsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-7.5};
const content = `<path class="xwwxjabsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:soundcloud" /></template>
