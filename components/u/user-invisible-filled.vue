<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msqd_f71t.css';
import '../../css/b/bh5yu-cer.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msqd_f71t"/><path class="bh5yu-cer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:user-invisible-filled" /></template>
