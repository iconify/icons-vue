<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzmp4vbdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bzmp4vbdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user-heart2" /></template>
