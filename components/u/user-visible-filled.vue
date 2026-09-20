<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bey0n9euq.css';
import '../../css/b/bh5yu-cer.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bey0n9euq"/><path class="bh5yu-cer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:user-visible-filled" /></template>
