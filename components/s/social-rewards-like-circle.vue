<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iefwlelij.css';
import '../../css/h/h7exl5bwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iefwlelij"/><path class="h7exl5bwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:social-rewards-like-circle" /></template>
